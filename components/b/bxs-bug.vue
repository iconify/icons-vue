<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqbp7ccct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqbp7ccct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bug" /></template>
