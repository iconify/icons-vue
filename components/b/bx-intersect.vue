<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bab7g1bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bab7g1bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-intersect" /></template>
