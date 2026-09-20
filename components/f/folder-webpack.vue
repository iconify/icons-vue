<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t00mbrv.css';
import '../../css/c/cc68579in.css';
import '../../css/l/lp2zuwhka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2t00mbrv"/><path class="cc68579in"/><path class="lp2zuwhka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-webpack" /></template>
