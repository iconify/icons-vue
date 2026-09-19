<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq-azk5il.css';
import '../../css/z/zu7-jfbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-azk5il"/><path class="zu7-jfbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:django" /></template>
