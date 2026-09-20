<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d6x9vjq6n.css';
import '../../css/s/sww6cebxb.css';
import '../../css/b/bwsf8zpll.css';
import '../../css/s/sr5bgubyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d6x9vjq6n"/><path class="sww6cebxb"/><path class="bwsf8zpll"/><path class="sr5bgubyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-2-linear" /></template>
