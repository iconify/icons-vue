<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9q5tbb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9q5tbb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ambulance" /></template>
