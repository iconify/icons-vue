<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfxiwybnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":432};
const content = `<path class="rfxiwybnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:input-hdmi" /></template>
