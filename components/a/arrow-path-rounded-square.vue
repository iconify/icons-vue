<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttrynm31t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttrynm31t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-rounded-square" /></template>
