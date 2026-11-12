<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nokhm-h5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nokhm-h5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:luna-dashboard-dark" /></template>
