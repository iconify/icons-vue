<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd4a3wzlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd4a3wzlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-3" /></template>
