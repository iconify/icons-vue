<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alx9w2vyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alx9w2vyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iberia" /></template>
