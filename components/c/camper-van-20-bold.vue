<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxzl1bc0g.css';
import '../../css/e/e6or4bcld.css';
import '../../css/a/a2_nmqdnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xxzl1bc0g"/><path class="e6or4bcld"/><path class="a2_nmqdnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camper-van-20-bold" /></template>
