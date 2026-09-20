<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emd2fydgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emd2fydgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:allowances-silence" /></template>
