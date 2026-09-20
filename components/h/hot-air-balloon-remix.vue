<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvp70pb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dvp70pb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hot-air-balloon-remix" /></template>
