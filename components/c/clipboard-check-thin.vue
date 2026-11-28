<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlzb69b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hlzb69b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clipboard-check-thin" /></template>
