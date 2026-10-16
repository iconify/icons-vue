<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3d17v-0n.css';
import '../../css/o/ok69a315p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3d17v-0n"/><path class="ok69a315p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ethernet-port-48" /></template>
