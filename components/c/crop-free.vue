<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzbmkwk2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzbmkwk2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:crop-free" /></template>
