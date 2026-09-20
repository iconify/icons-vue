<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyad3cctd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zyad3cctd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:folder-plus" /></template>
