<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3qu_cu4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="l3qu_cu4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:listalt" /></template>
