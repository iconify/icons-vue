<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqv-4hvik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqv-4hvik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:gas-pump" /></template>
