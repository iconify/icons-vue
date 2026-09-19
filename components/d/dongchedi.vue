<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1v12nz2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j1v12nz2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dongchedi" /></template>
