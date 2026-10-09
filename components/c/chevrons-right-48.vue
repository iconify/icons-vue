<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0obyhbch.css';
import '../../css/z/zlt4eiz7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e0obyhbch"/><path class="zlt4eiz7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-right-48" /></template>
