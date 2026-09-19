<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewkexkzaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewkexkzaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:list-alt" /></template>
