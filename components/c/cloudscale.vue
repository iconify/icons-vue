<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhb_aqb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qhb_aqb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cloudscale" /></template>
