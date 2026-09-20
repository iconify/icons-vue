<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13isnbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p13isnbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:heading-3-paragraph-styles-heading" /></template>
