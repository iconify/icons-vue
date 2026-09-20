<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_zuvlbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="d_zuvlbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:car-dealer" /></template>
