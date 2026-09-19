<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_6lzl0ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="u_6lzl0ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:etsy" /></template>
