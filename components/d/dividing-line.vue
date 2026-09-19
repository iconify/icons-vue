<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n08ut8bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n08ut8bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dividing-line" /></template>
