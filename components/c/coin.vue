<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ho5fb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2ho5fb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:coin" /></template>
