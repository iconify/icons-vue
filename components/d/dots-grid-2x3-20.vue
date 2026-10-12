<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2dwvmnwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f2dwvmnwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dots-grid-2x3-20" /></template>
