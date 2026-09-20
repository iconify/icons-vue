<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmoq09uml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmoq09uml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ampl" /></template>
