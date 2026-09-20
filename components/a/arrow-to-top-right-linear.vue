<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5y010g_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5y010g_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-top-right-linear" /></template>
