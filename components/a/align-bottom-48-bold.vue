<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8u9mrbde.css';
import '../../css/z/znkjny7ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="znkjny7ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-bottom-48-bold" /></template>
