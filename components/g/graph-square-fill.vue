<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw__72b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fw__72b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:graph-square-fill" /></template>
