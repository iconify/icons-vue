<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/le2xeyb8c.css';
import '../../css/e/ewiisvbxm.css';
import '../../css/s/s7qktox6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le2xeyb8c"/><path class="ewiisvbxm"/><path class="s7qktox6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-image" /></template>
