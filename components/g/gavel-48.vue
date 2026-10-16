<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opt71mb5e.css';
import '../../css/k/k1vorjqdj.css';
import '../../css/r/rg1xqfbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="opt71mb5e"/><path class="k1vorjqdj"/><path class="rg1xqfbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gavel-48" /></template>
