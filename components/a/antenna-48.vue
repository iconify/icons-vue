<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnzn_vsno.css';
import '../../css/v/vl-e_fb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dnzn_vsno"/><path class="vl-e_fb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:antenna-48" /></template>
