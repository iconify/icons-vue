<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq128jbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uq128jbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:cloud-upload" /></template>
