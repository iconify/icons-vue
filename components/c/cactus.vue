<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmb1as-8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bmb1as-8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:cactus" /></template>
