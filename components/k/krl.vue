<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z95yftb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z95yftb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:krl" /></template>
