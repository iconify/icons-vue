<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e31ik5bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e31ik5bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-left-bottom-right-bold" /></template>
