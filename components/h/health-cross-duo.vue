<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy7mlyd3q.css';
import '../../css/i/iet5dccbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sy7mlyd3q"/><path class="iet5dccbc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:health-cross-duo" /></template>
