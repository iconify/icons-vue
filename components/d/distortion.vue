<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b18_34_hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b18_34_hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:distortion" /></template>
