<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgm-muboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zgm-muboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-arrow-down-fill-20" /></template>
