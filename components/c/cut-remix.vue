<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdrwgyy_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xdrwgyy_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cut-remix" /></template>
