<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4h2do-8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4h2do-8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:external-link" /></template>
