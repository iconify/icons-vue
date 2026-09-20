<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-05_siio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-05_siio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-down-dashed" /></template>
