<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4qksuoeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4qksuoeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:archicad" /></template>
