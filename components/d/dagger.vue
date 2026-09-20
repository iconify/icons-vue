<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8mohmb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u8mohmb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dagger" /></template>
