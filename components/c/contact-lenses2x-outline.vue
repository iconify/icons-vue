<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz752qb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dz752qb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contact-lenses2x-outline" /></template>
