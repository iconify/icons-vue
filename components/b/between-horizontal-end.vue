<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffnxunbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffnxunbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:between-horizontal-end" /></template>
