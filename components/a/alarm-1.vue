<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0piq7bju.css';
import '../../css/j/jqhsxpb4d.css';
import '../../css/r/rztgfrb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0piq7bju"/><path class="jqhsxpb4d"/><path clip-rule="evenodd" class="rztgfrb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:alarm-1" /></template>
