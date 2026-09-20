<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_q8l3bsv.css';
import '../../css/a/agp2gjbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_q8l3bsv"/><path class="agp2gjbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-superset-light" /></template>
