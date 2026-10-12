<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy3btfbfu.css';
import '../../css/b/b79ewjo9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fy3btfbfu"/><path class="b79ewjo9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brain-48-bold" /></template>
