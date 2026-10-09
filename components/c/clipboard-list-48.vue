<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxzfl5btn.css';
import '../../css/w/wsygfsbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lxzfl5btn"/><path class="wsygfsbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-list-48" /></template>
