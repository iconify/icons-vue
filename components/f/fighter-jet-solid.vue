<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwbfe-b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwbfe-b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fighter-jet-solid" /></template>
