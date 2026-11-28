<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwairyb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwairyb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dot-solid" /></template>
