<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4jdtubrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4jdtubrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:armchair-fill" /></template>
