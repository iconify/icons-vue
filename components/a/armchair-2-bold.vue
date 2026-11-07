<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4b0zsbme.css';
import '../../css/q/q9j565bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4b0zsbme"/><path class="q9j565bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-2-bold" /></template>
