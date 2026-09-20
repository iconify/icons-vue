<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arf4c6btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arf4c6btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-bold" /></template>
