<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/see3_bcxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="see3_bcxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:localxpose" /></template>
