<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naqry0ggt.css';
import '../../css/o/olslqwbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="naqry0ggt"/><path class="olslqwbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidifier-48" /></template>
