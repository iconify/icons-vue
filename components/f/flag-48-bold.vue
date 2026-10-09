<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8l_jsz-q.css';
import '../../css/r/rodd6kbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8l_jsz-q"/><path class="rodd6kbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-48-bold" /></template>
