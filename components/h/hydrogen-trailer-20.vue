<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxm1vbcze.css';
import '../../css/c/cdve484mo.css';
import '../../css/x/xwbticcgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxm1vbcze"/><path class="cdve484mo"/><path class="xwbticcgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-trailer-20" /></template>
