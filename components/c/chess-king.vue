<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phkpb-2vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="phkpb-2vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-king" /></template>
