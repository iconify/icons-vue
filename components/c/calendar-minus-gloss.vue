<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gghi3zbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gghi3zbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-minus-gloss" /></template>
