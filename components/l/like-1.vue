<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0pgy-bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v0pgy-bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:like-1" /></template>
