<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z662ojbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z662ojbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-horizontal-48" /></template>
