<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y--ny7bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y--ny7bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ejabberd-light" /></template>
