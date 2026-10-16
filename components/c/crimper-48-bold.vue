<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al8t810di.css';
import '../../css/x/xtbtl4t9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="al8t810di"/><path class="xtbtl4t9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crimper-48-bold" /></template>
