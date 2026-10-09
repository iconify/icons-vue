<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdoju7bng.css';
import '../../css/v/vbtr2ykcx.css';
import '../../css/z/zkd6-wbyc.css';
import '../../css/h/h11x-xb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdoju7bng"/><path class="vbtr2ykcx"/><path class="zkd6-wbyc"/><path class="h11x-xb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biomass-48" /></template>
