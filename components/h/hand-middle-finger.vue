<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf2bjwbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uf2bjwbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-middle-finger" /></template>
