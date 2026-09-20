<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjodv2swo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjodv2swo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:instrument-classical-piano-bold" /></template>
