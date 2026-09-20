<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrc-9yb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mrc-9yb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-move-solid" /></template>
