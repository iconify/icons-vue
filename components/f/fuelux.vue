<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpl4w9bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpl4w9bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fuelux" /></template>
