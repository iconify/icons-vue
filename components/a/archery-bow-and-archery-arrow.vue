<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx_mgsb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lx_mgsb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:archery-bow-and-archery-arrow" /></template>
