<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3oma6ihu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3oma6ihu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:easy" /></template>
