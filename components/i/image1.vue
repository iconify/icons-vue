<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rueir2m3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rueir2m3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:image1" /></template>
