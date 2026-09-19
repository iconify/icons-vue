<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xdadzovzv.css';
import '../../css/z/zebsf4wkp.css';
import '../../css/d/dfl2z7ovp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdadzovzv"/><path class="zebsf4wkp"/><path class="dfl2z7ovp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-notification" /></template>
