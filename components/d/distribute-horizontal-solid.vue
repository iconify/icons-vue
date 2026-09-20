<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs6p-wb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rs6p-wb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:distribute-horizontal-solid" /></template>
