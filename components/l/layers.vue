<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvyp8lo5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvyp8lo5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:layers" /></template>
