<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-scc5p3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-scc5p3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:browser" /></template>
