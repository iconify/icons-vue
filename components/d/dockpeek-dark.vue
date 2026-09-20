<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngjilubfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngjilubfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockpeek-dark" /></template>
