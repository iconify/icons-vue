<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3b3aw3dq.css';
import '../../css/v/v7n04acgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3b3aw3dq"/><path class="v7n04acgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:audit-48" /></template>
