<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-lvsxb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h-lvsxb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:image-fill-12" /></template>
