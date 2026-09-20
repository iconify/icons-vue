<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz7-hy8bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gz7-hy8bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fried-egg-breakfast-solid" /></template>
