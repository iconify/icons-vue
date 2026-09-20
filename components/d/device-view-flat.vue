<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9uamdkws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9uamdkws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:device-view-flat" /></template>
