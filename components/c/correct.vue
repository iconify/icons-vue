<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at03s0y1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="at03s0y1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:correct" /></template>
