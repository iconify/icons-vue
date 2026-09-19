<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/papalo4pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="papalo4pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-aperture" /></template>
