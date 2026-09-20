<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf8916bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf8916bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-variant-on" /></template>
