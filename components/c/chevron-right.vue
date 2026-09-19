<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz5w6354e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jz5w6354e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-right" /></template>
