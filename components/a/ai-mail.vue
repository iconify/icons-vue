<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/w6b3lzbgx.css';
import '../../css/s/sr_zc7bwn.css';
import '../../css/d/dd5nscbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6b3lzbgx"/><path class="sr_zc7bwn"/><path class="dd5nscbtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-mail" /></template>
