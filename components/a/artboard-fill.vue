<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd0xs_bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd0xs_bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:artboard-fill" /></template>
