<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6p8dpbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6p8dpbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:intersect-line" /></template>
