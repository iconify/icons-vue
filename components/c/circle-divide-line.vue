<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e029o1r4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e029o1r4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-divide-line" /></template>
