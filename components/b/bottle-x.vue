<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob5_q808q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob5_q808q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bottle-x" /></template>
