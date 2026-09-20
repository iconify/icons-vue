<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed6qwbapg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed6qwbapg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:history" /></template>
