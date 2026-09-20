<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkb05-p-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vkb05-p-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-two-rtl" /></template>
