<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5t-s_b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l5t-s_b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:invisible-1-remix" /></template>
