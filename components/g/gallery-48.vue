<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acc9x56xd.css';
import '../../css/q/qj8k73bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="acc9x56xd"/><path class="qj8k73bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gallery-48" /></template>
