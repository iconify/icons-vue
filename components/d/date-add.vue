<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjhk3mbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sjhk3mbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:date-add" /></template>
