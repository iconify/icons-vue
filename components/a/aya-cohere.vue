<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfwm6qbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfwm6qbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aya-cohere" /></template>
