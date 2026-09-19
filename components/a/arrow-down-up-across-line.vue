<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq-3olb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dq-3olb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-down-up-across-line" /></template>
