<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekjul2jux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekjul2jux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garmin-grafana-light" /></template>
