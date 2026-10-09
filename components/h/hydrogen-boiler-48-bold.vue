<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zanasbbem.css';
import '../../css/d/dgdz7cczj.css';
import '../../css/j/jvxstphxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zanasbbem"/><path class="dgdz7cczj"/><path class="jvxstphxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-boiler-48-bold" /></template>
