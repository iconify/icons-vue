<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ym0rb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="l1ym0rb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:brush-1-rotated" /></template>
