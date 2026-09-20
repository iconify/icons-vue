<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie0mq3i_d.css';
import '../../css/k/kgzgwquda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ie0mq3i_d"/><path class="kgzgwquda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelope" /></template>
