<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgqvtfezh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqvtfezh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:key-round-x" /></template>
