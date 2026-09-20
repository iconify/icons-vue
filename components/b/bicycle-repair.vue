<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlyg5ji_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tlyg5ji_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bicycle-repair" /></template>
