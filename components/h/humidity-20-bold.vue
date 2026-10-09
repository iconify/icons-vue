<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b68k1jbxl.css';
import '../../css/d/despmrd_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b68k1jbxl"/><path class="despmrd_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidity-20-bold" /></template>
