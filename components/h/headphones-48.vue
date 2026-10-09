<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf7rtccfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zf7rtccfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headphones-48" /></template>
