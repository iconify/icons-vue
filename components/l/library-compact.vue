<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quwyzac4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="quwyzac4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:library-compact" /></template>
