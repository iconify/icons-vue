<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do5a3zb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="do5a3zb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bat-48" /></template>
