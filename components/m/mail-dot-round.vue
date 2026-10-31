<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_d--j0mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_d--j0mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-round" /></template>
