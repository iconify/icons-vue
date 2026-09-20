<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi21tmbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xi21tmbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airport-plane-remix" /></template>
