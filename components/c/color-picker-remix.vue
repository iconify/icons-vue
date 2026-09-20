<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0bpyjbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v0bpyjbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:color-picker-remix" /></template>
