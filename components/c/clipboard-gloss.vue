<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1ok0bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp1ok0bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-gloss" /></template>
