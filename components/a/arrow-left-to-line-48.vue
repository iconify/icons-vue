<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdyaxkb1l.css';
import '../../css/e/e3qz-bbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdyaxkb1l"/><path class="e3qz-bbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-to-line-48" /></template>
