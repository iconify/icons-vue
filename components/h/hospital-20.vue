<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-z0-wtpr.css';
import '../../css/c/c2yq94b2t.css';
import '../../css/j/jwhg0sbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e-z0-wtpr"/><path class="c2yq94b2t"/><path class="jwhg0sbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hospital-20" /></template>
