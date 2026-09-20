<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4wpf8y_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y4wpf8y_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graduation-cap-remix" /></template>
