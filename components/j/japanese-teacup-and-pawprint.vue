<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5i_mx52w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r5i_mx52w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:japanese-teacup-and-pawprint" /></template>
