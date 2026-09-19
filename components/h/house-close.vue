<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k59jp2z-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k59jp2z-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-close" /></template>
