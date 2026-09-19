<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyoj5g2zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qyoj5g2zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-four" /></template>
