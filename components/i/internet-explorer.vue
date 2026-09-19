<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z69p_lzea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="z69p_lzea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:internet-explorer" /></template>
