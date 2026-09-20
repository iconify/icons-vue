<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/annzx-b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="annzx-b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location" /></template>
