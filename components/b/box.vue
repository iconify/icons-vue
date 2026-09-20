<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gef84bcbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gef84bcbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:box" /></template>
