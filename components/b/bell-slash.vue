<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/i-50d2biz.css';
import '../../css/s/sdp6-tbwn.css';
import '../../css/t/t4o8ctohm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="i-50d2biz"/><path class="sdp6-tbwn"/><path class="i-50d2biz"/><path class="t4o8ctohm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:bell-slash" /></template>
