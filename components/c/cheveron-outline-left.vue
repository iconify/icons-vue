<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um-ib7b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="um-ib7b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:cheveron-outline-left" /></template>
