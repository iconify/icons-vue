<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o07pescwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o07pescwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hulu-live-tv-logo-block" /></template>
