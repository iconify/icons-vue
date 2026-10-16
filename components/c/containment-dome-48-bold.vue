<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa_132r-y.css';
import '../../css/i/ihmii9b0s.css';
import '../../css/t/tiqwyoept.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qa_132r-y"/><path class="ihmii9b0s"/><path class="tiqwyoept"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:containment-dome-48-bold" /></template>
