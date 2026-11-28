<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxg1zz31j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxg1zz31j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:apple-heart" /></template>
