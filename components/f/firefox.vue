<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zub53eaid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zub53eaid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:firefox" /></template>
