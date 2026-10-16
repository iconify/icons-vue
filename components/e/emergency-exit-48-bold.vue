<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9e0p_b-j.css';
import '../../css/b/b34wfpb4d.css';
import '../../css/e/eg_6x1bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9e0p_b-j"/><path class="b34wfpb4d"/><path class="eg_6x1bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emergency-exit-48-bold" /></template>
