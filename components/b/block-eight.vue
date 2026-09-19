<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fct2vly4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fct2vly4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-eight" /></template>
