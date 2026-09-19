<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omm57_y2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omm57_y2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-seven" /></template>
