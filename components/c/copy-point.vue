<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nda5gnl9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nda5gnl9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:copy-point" /></template>
