<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7lu9sbrx.css';
import '../../css/r/rqz9a6b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7lu9sbrx"/><path class="rqz9a6b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-to-line-48" /></template>
