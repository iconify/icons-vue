<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5j900bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c5j900bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bug" /></template>
