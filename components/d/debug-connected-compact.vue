<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm9z_xbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="bm9z_xbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-connected-compact" /></template>
