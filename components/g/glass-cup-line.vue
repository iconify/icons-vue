<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg2b60bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg2b60bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:glass-cup-line" /></template>
