<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpb05ru6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bpb05ru6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:evergreen-tree" /></template>
