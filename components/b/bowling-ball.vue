<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw5a7nblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bw5a7nblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bowling-ball" /></template>
