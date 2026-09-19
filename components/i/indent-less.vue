<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0kkqwbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w0kkqwbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:indent-less" /></template>
