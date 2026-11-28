<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj7b2nb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj7b2nb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bluetooth-search" /></template>
