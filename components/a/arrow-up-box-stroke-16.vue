<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd3uh_z7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hd3uh_z7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-up-box-stroke-16" /></template>
