<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k26-hfmon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k26-hfmon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-1" /></template>
