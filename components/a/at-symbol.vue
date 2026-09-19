<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2622zbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2622zbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:at-symbol" /></template>
