<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d88tubblx.css';
import '../../css/a/a3i1g1emt.css';
import '../../css/q/qayriggpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d88tubblx"/><path class="a3i1g1emt"/><path class="qayriggpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cell-48" /></template>
