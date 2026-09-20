<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf4ef19gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lf4ef19gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-coordinate-axis-solid" /></template>
