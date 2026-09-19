<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6vyf9bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="z6vyf9bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:app-store" /></template>
