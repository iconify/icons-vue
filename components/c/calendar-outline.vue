<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jh5366bnn.css';
import '../../css/t/tz4ef46-b.css';
import '../../css/t/to1k2cb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="calendar-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="jh5366bnn"/><path clip-rule="evenodd" class="tz4ef46-b"/><path class="to1k2cb9y"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:calendar-outline" /></template>
