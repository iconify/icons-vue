<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpoc-qgmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpoc-qgmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluidcalendar-light" /></template>
