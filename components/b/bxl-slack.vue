<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/resbl2q7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="resbl2q7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-slack" /></template>
