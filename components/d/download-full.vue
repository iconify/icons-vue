<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtzxaybae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtzxaybae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:download-full" /></template>
