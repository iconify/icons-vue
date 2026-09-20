<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_9fuxcko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="h_9fuxcko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:blind" /></template>
