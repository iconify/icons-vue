<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmc3uq-pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmc3uq-pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-text" /></template>
