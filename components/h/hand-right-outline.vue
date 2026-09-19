<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grhtrnaya.css';
import '../../css/o/ohiekfb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grhtrnaya"/><path class="ohiekfb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hand-right-outline" /></template>
