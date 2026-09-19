<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orbmf1k0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="orbmf1k0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:amazon" /></template>
