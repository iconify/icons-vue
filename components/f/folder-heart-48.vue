<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9x9-c_l.css';
import '../../css/r/rfebmmxan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/><path class="rfebmmxan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-heart-48" /></template>
