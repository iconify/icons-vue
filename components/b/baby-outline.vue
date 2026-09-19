<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4sfmobcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r4sfmobcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baby-outline" /></template>
