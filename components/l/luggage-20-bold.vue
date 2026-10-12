<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncjcrccsd.css';
import '../../css/w/wfyvh_b2x.css';
import '../../css/r/r5bqwybgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncjcrccsd"/><path class="wfyvh_b2x"/><path class="r5bqwybgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:luggage-20-bold" /></template>
