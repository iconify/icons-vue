<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrlfoibil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrlfoibil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:card" /></template>
