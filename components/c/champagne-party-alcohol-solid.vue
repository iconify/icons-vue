<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjnkcmwsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jjnkcmwsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:champagne-party-alcohol-solid" /></template>
