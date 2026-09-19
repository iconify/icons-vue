<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujdi-5u_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ujdi-5u_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-alt" /></template>
