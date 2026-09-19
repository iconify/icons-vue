<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3g8tezhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g3g8tezhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bike-outline" /></template>
