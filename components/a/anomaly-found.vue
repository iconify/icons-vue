<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbcd8xbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbcd8xbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:anomaly-found" /></template>
