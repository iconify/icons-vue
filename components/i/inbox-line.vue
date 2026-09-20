<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux06hx6gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux06hx6gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inbox-line" /></template>
