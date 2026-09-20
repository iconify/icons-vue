<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-j27gaxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-j27gaxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-t" /></template>
