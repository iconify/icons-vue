<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bns68ccvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bns68ccvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:inkscape" /></template>
