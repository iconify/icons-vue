<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy11ypbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oy11ypbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bluetooth-remix" /></template>
