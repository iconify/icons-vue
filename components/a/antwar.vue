<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy6eb_buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gy6eb_buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:antwar" /></template>
