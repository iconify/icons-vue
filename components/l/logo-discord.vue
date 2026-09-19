<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ces_7v8dp.css';
import '../../css/k/khz-3ib7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ces_7v8dp"/><path class="khz-3ib7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-discord" /></template>
