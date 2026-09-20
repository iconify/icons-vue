<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0ch54b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f0ch54b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-bottom-outline" /></template>
