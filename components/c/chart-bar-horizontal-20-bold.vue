<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iztj1m4kj.css';
import '../../css/m/mr6auulay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iztj1m4kj"/><path class="mr6auulay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-horizontal-20-bold" /></template>
