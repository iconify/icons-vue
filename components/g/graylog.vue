<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uju6rdxwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uju6rdxwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:graylog" /></template>
