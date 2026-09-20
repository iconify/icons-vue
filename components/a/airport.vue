<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9_1p1ist.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9_1p1ist"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airport" /></template>
