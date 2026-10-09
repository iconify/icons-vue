<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tptd5ygch.css';
import '../../css/i/iklw8pg9o.css';
import '../../css/r/r2a1kcczy.css';
import '../../css/b/b0a2wmopo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tptd5ygch"/><path class="iklw8pg9o"/><path class="r2a1kcczy"/><path class="b0a2wmopo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:atom-48-bold" /></template>
