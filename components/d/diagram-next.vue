<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xotfa1b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xotfa1b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:diagram-next" /></template>
