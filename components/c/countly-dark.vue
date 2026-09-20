<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiidpcdve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kiidpcdve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:countly-dark" /></template>
