<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prd4v3_sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prd4v3_sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:filmstrip" /></template>
