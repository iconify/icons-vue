<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm9ywsb4k.css';
import '../../css/e/eipzjac9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lm9ywsb4k"/><path class="eipzjac9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clipboard-pulse" /></template>
