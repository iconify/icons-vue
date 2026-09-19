<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w336_2pbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w336_2pbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-big-round" /></template>
