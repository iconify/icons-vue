<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ld50e8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ld50e8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:id-card-x" /></template>
