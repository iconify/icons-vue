<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gte4k_rwf.css';
import '../../css/l/lmhgg8f3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gte4k_rwf"/><path class="lmhgg8f3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:history-stroke-20" /></template>
