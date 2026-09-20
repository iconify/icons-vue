<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi_xcka2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fi_xcka2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ganttchart" /></template>
