<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umb8jtbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umb8jtbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-flickr-square" /></template>
