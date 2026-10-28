<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbh-1ccij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbh-1ccij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:debian" /></template>
