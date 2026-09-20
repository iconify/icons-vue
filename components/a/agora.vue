<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml94e4_dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml94e4_dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:agora" /></template>
