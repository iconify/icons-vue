<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_oyrm6dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_oyrm6dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hexagon" /></template>
