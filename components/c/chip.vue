<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qboix9yzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qboix9yzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chip" /></template>
