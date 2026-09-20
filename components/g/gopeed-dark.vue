<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki1q34b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ki1q34b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gopeed-dark" /></template>
