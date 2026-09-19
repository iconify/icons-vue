<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yssde8b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="yssde8b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-left" /></template>
