<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi0h6hbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0h6hbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-line" /></template>
