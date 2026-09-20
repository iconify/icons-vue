<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iir0f5bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="iir0f5bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:city-11" /></template>
