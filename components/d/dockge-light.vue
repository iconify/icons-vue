<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atehkzbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="atehkzbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockge-light" /></template>
