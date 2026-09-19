<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgs_pek_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mgs_pek_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flag" /></template>
