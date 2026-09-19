<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2ogq0u7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2ogq0u7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-windows" /></template>
