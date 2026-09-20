<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u89-i4iqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u89-i4iqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-open-blank-variant-outline" /></template>
