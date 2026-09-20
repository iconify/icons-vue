<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1_08bcdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q1_08bcdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:intellectual-remix" /></template>
