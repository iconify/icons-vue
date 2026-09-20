<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4b_bdchh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4b_bdchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cross-seed-light" /></template>
