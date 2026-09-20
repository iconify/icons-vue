<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv9ej7bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qv9ej7bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:foss-events-dark" /></template>
