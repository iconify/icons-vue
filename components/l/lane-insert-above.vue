<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-y0q6rwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v-y0q6rwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:lane-insert-above" /></template>
