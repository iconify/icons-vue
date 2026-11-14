<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lzm7kvups.css';
import '../../css/a/a-z24ibwd.css';
import '../../css/k/kctaqhqoj.css';
import '../../css/q/q8ijdsmrx.css';
import '../../css/g/gb0ft43tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lzm7kvups"/><circle class="a-z24ibwd"/><path class="kctaqhqoj"/><path class="q8ijdsmrx"/><path class="gb0ft43tq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:bike-electric" /></template>
