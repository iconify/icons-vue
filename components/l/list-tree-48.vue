<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7vs37bmn.css';
import '../../css/t/t1-50l-2z.css';
import '../../css/e/e7avd0rgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a7vs37bmn"/><path class="t1-50l-2z"/><path class="e7avd0rgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-tree-48" /></template>
