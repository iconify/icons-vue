<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1q4otbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1q4otbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-both" /></template>
