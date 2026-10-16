<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u95e4sw8e.css';
import '../../css/l/la89sqemp.css';
import '../../css/d/d1s4subwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u95e4sw8e"/><path class="la89sqemp"/><path class="d1s4subwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-copy-48-bold" /></template>
