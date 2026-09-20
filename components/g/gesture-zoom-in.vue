<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvy--ybuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvy--ybuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:gesture-zoom-in" /></template>
