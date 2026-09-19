<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o76u42bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o76u42bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-circle-filled" /></template>
