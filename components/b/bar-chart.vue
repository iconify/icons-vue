<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgpe9kb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgpe9kb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:bar-chart" /></template>
