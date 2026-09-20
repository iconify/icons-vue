<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jabfj5b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jabfj5b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:dead-tree" /></template>
