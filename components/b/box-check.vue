<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/size2fbdv.css';
import '../../css/u/uk7hokb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="size2fbdv"/><path class="uk7hokb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-check" /></template>
