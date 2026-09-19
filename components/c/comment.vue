<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4s7ccb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4s7ccb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:comment" /></template>
