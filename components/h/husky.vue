<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqt35052q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqt35052q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:husky" /></template>
