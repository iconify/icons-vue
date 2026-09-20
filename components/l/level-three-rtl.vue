<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvjku0arf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qvjku0arf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-three-rtl" /></template>
