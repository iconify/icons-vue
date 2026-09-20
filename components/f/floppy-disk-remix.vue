<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i36-3_fmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i36-3_fmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:floppy-disk-remix" /></template>
