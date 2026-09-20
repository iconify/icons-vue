<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2iv7saz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ml2iv7saz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agam-space-dark" /></template>
