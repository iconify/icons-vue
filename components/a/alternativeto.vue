<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdfsed2ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdfsed2ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alternativeto" /></template>
