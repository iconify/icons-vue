<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc0abgbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0abgbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-strava" /></template>
