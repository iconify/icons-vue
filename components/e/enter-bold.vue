<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ma0q-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ma0q-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:enter-bold" /></template>
