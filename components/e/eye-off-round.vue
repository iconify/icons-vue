<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mygkryb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mygkryb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-round" /></template>
