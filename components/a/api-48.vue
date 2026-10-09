<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzeztmj2w.css';
import '../../css/j/jq2f_o2_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzeztmj2w"/><path class="jq2f_o2_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-48" /></template>
