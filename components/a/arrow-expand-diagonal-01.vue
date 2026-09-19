<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixfbf2bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixfbf2bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-expand-diagonal-01" /></template>
