<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x33k5bbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x33k5bbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cross-seed-dark" /></template>
