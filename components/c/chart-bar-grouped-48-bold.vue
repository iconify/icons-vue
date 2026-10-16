<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8u9mrbde.css';
import '../../css/y/ygsi-xb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="ygsi-xb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-grouped-48-bold" /></template>
