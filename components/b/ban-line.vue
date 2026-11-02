<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqqss1byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqqss1byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ban-line" /></template>
