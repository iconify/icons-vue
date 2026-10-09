<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q668lybvz.css';
import '../../css/w/wxvvsl_vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q668lybvz"/><path class="wxvvsl_vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type1-48-bold" /></template>
