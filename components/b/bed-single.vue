<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm97-6bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm97-6bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single" /></template>
