<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujimcnb1a.css';
import '../../css/w/wuwoojhmz.css';
import '../../css/v/v4s55l-rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ujimcnb1a"/><path class="wuwoojhmz"/><path class="v4s55l-rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-meter-20-bold" /></template>
