<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9x-w4s1u.css';
import '../../css/o/omx4q5uyw.css';
import '../../css/x/xqh2mbcfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9x-w4s1u"/><path class="omx4q5uyw"/><path class="xqh2mbcfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-truck-20-bold" /></template>
