<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vph7o5b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vph7o5b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fire-hydrant-alert" /></template>
