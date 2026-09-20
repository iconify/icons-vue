<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohfh2ubyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohfh2ubyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:invisible-2-solid" /></template>
