<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wug0x-_oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wug0x-_oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:globe" /></template>
