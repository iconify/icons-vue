<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh4mktbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh4mktbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dwm" /></template>
