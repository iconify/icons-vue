<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8u9mrbde.css';
import '../../css/o/oum-_kb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="oum-_kb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-48-bold" /></template>
