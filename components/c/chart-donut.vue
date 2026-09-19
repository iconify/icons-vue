<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8jaru_ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q8jaru_ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chart-donut" /></template>
