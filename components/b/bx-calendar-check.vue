<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfc4wub2q.css';
import '../../css/r/r2ojm4wqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfc4wub2q"/><path class="r2ojm4wqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-calendar-check" /></template>
