<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegrs6bql.css';
import '../../css/o/o7hd-nb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="o7hd-nb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electricity-bill-48" /></template>
