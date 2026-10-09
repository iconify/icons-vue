<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn3kjzbic.css';
import '../../css/v/v9nux6bhi.css';
import '../../css/s/shy242ktc.css';
import '../../css/w/whslaccyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tn3kjzbic"/><path class="v9nux6bhi"/><path class="shy242ktc"/><path class="whslaccyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gantry-crane-20" /></template>
