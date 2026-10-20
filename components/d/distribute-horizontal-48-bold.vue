<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brn74nbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="brn74nbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-horizontal-48-bold" /></template>
