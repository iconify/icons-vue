<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlvssrboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zlvssrboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:box-3d-fill-12" /></template>
