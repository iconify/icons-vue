<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_y_-wofq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_y_-wofq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-up-circle-sharp" /></template>
