<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auc171b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="auc171b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeradius-dark" /></template>
