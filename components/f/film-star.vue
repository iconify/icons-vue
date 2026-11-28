<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy027wbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy027wbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:film-star" /></template>
