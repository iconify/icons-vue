<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl818kyew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl818kyew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helm-dark" /></template>
