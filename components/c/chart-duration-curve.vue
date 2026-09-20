<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/procg5tah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="procg5tah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-duration-curve" /></template>
