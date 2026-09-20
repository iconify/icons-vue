<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ndoqbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":371};
const content = `<path class="l9ndoqbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:decathlon-logo" /></template>
