<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-fl_btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf-fl_btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:archive-search" /></template>
