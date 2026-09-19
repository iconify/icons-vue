<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/ruvu4yxzk.css';
import '../../css/i/i1cd8bsmc.css';
import '../../css/i/iexuhfb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruvu4yxzk"/><path class="i1cd8bsmc"/><path class="iexuhfb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:citrus" /></template>
