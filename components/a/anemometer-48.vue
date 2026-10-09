<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9gapcbyd.css';
import '../../css/x/xx5tdhvbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9gapcbyd"/><path class="xx5tdhvbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anemometer-48" /></template>
