<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg5mlp8ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg5mlp8ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrows-contract-expressive" /></template>
