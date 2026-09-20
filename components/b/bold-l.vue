<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orlvco9_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="orlvco9_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-l" /></template>
