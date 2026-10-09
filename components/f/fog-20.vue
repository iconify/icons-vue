<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8vmzc-sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8vmzc-sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fog-20" /></template>
