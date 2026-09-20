<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxp_azbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxp_azbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-r" /></template>
