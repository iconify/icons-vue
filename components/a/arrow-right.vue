<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd3cd6ubq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qd3cd6ubq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-right" /></template>
