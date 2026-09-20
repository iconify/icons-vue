<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibz29_uar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibz29_uar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-arrow-up" /></template>
