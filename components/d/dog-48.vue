<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4_-hv4ce.css';
import '../../css/c/cty3yck3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t4_-hv4ce"/><path class="cty3yck3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dog-48" /></template>
