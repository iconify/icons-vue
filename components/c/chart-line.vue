<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0o9798fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0o9798fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-line" /></template>
