<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1pix1bws.css';
import '../../css/r/rugjrsblu.css';
import '../../css/z/z6kf3ab0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1pix1bws"/><path class="rugjrsblu"/><path class="z6kf3ab0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:collections-bookmark" /></template>
