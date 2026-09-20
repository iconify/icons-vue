<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icz9uqvnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icz9uqvnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kodular" /></template>
