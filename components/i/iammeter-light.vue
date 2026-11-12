<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bypt6tfji.css';
import '../../css/x/x6lp5sbsv.css';
import '../../css/y/yxbj3znwq.css';
import '../../css/o/oj59phb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bypt6tfji"/><path class="x6lp5sbsv"/><path class="yxbj3znwq"/><path class="oj59phb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iammeter-light" /></template>
