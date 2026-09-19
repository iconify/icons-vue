<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwyo20bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qwyo20bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-center" /></template>
