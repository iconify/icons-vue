<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pufh1-b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pufh1-b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:dollar" /></template>
