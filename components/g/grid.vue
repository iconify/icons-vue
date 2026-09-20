<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69cxl6mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f69cxl6mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:grid" /></template>
