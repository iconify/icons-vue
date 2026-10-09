<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xldecsnzb.css';
import '../../css/v/vgmnx8bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xldecsnzb"/><path class="vgmnx8bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iron-20-bold" /></template>
