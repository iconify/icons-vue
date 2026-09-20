<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swwt4xbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swwt4xbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fsharp" /></template>
