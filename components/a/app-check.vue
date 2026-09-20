<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzq7f1bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzq7f1bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-check" /></template>
