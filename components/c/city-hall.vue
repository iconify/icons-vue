<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffx8j-san.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ffx8j-san"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:city-hall" /></template>
