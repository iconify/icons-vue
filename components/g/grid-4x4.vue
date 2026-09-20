<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vef-s7bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vef-s7bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grid-4x4" /></template>
