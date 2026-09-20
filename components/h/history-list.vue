<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7n0j6bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u7n0j6bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:history-list" /></template>
