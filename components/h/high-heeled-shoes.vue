<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyh8ppbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oyh8ppbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:high-heeled-shoes" /></template>
