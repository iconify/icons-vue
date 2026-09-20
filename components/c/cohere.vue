<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a04tfwkss.css';
import '../../css/y/yv0epcrue.css';
import '../../css/w/weac8tb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":75,"height":75};
const content = `<path class="a04tfwkss"/><path class="yv0epcrue"/><path class="weac8tb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cohere" /></template>
