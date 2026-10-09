<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6bo5g7fy.css';
import '../../css/p/p0blm-arr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6bo5g7fy"/><path class="p0blm-arr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jar-48" /></template>
