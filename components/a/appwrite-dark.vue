<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owku8vbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owku8vbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:appwrite-dark" /></template>
