<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by2b1m5vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by2b1m5vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bounding-box-solid" /></template>
