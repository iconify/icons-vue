<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfj70_hgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfj70_hgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:electric-cooker-line" /></template>
