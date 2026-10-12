<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhk4ll00z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhk4ll00z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:equal-48" /></template>
