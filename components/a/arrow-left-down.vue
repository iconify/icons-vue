<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzk5obbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lzk5obbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-left-down" /></template>
