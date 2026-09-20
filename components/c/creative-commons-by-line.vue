<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u06v9hc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u06v9hc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-by-line" /></template>
