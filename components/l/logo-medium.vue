<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-6li450q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-6li450q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-medium" /></template>
