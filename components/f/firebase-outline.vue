<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx8h4crue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vx8h4crue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:firebase-outline" /></template>
