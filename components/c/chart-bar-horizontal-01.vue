<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcyu-v6zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcyu-v6zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chart-bar-horizontal-01" /></template>
