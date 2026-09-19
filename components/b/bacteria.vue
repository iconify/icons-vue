<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhgbhibvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jhgbhibvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bacteria" /></template>
