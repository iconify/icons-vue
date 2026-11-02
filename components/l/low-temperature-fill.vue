<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfy-2kbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfy-2kbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-temperature-fill" /></template>
