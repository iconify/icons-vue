<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/omhvxckds.css';
import '../../css/v/v0ldy8l7g.css';
import '../../css/k/kmh5_x81g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="omhvxckds"/><path class="v0ldy8l7g"/><path class="kmh5_x81g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-close-linear" /></template>
