<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyl5n_bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wyl5n_bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kids-train" /></template>
