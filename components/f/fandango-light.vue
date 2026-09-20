<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt_9hnz1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vt_9hnz1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fandango-light" /></template>
