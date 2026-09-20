<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr2nrvggc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jr2nrvggc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:airplane-disabled-solid" /></template>
