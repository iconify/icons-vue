<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcs6_gbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="gcs6_gbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:credit-card" /></template>
