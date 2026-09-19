<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y28ds_u5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y28ds_u5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:four-duo" /></template>
