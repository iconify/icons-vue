<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pymb-abua.css';
import '../../css/r/r1etijbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pymb-abua"/><path class="r1etijbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:gem-a" /></template>
