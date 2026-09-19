<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mica3mhlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="mica3mhlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alert-circle" /></template>
