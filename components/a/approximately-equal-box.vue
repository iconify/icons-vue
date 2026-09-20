<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd-8lcb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd-8lcb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:approximately-equal-box" /></template>
