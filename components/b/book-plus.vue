<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u53v_5bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u53v_5bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:book-plus" /></template>
