<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrtgb7mac.css';
import '../../css/s/swkhaseke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wrtgb7mac"/><path class="swkhaseke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-resiliency" /></template>
