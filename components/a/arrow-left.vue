<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o66mqobum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o66mqobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-left" /></template>
