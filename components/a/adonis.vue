<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5s0_hb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path paint-order="fill markers stroke" class="l5s0_hb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:adonis" /></template>
