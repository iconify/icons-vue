<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciarmei3k.css';
import '../../css/n/nafa54a1z.css';
import '../../css/o/ofvhr7lmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ciarmei3k"/><path class="nafa54a1z"/><path class="ofvhr7lmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layers-48" /></template>
