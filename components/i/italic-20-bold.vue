<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k40yvq1wf.css';
import '../../css/e/e1pitrb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k40yvq1wf"/><path class="e1pitrb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:italic-20-bold" /></template>
