<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnwy0xbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bnwy0xbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:magnifying-glass-x-thin" /></template>
