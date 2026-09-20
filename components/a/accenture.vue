<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-e6l2b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-e6l2b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:accenture" /></template>
