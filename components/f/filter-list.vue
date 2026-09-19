<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar-x8db-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ar-x8db-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:filter-list" /></template>
