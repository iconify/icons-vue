<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-ux5kblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-ux5kblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:calendar-3" /></template>
