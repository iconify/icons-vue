<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcgu1x-sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wcgu1x-sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:global-nav-button-active" /></template>
