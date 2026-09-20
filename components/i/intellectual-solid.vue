<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu6k__gts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pu6k__gts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:intellectual-solid" /></template>
