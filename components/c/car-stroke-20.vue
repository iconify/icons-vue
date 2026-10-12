<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tem_62y7z.css';
import '../../css/y/yx0hc3b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tem_62y7z"/><path class="yx0hc3b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:car-stroke-20" /></template>
