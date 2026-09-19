<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thk55vbks.css';
import '../../css/o/o6e3x-bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thk55vbks"/><path class="o6e3x-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-fill-16" /></template>
