<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1te_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1te_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-k-circle" /></template>
