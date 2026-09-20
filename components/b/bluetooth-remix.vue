<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruy4n5q6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ruy4n5q6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bluetooth-remix" /></template>
