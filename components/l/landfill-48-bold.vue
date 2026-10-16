<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg667-8na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg667-8na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-48-bold" /></template>
