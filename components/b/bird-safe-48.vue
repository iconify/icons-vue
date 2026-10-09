<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs628n7li.css';
import '../../css/i/is5s5qqcb.css';
import '../../css/r/r5wz4ccht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xs628n7li"/><path class="is5s5qqcb"/><path class="r5wz4ccht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-safe-48" /></template>
