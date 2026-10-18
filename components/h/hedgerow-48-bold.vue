<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y83ielkqr.css';
import '../../css/y/y-605nsjq.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y83ielkqr"/><path class="y-605nsjq"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hedgerow-48-bold" /></template>
