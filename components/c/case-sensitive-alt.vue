<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxgv3ovom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxgv3ovom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:case-sensitive-alt" /></template>
