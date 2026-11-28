<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7d_2ebts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7d_2ebts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cabin-heart" /></template>
