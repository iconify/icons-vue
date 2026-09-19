<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bao1vbqnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bao1vbqnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:christmas-tree-one" /></template>
