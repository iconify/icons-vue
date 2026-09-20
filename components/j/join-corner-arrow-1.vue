<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8s82qb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8s82qb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-1" /></template>
