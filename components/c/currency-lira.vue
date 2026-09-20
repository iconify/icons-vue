<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjlhptqgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjlhptqgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-lira" /></template>
