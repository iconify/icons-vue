<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udiq2659b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udiq2659b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:audio-input-rca" /></template>
