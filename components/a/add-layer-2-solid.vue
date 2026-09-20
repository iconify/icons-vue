<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5mb7ejud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r5mb7ejud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:add-layer-2-solid" /></template>
