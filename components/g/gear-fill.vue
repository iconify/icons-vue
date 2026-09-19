<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1xznpkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kd1xznpkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:gear-fill" /></template>
