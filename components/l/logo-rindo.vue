<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edg0qh-xn.css';
import '../../css/a/am03yhn7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edg0qh-xn"/><path class="am03yhn7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-rindo" /></template>
