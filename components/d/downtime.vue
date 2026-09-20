<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpj0icx7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lpj0icx7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:downtime" /></template>
