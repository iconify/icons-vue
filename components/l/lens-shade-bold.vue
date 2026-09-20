<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d09fbgrfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d09fbgrfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lens-shade-bold" /></template>
