<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snn4fxhfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snn4fxhfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:imdb-logo" /></template>
