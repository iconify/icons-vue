<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyrr7ohpi.css';
import '../../css/v/v_nw6fb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyrr7ohpi"/><path class="v_nw6fb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garden-bench-48" /></template>
