<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw6idgbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw6idgbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bike-off" /></template>
