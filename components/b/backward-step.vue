<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icfk7ac_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="icfk7ac_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:backward-step" /></template>
