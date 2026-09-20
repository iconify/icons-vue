<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwk8eab6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwk8eab6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-rar-filled" /></template>
