<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orjswn0hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orjswn0hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-forward-circle" /></template>
