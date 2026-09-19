<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da0f09byt.css';
import '../../css/l/l8agopb9m.css';
import '../../css/z/zf8yduldz.css';
import '../../css/b/bz62vsbth.css';
import '../../css/n/n703s5ldj.css';
import '../../css/y/y1ejnebhn.css';
import '../../css/a/azg-b8b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da0f09byt"/><path class="l8agopb9m"/><path class="zf8yduldz"/><path class="bz62vsbth"/><path class="n703s5ldj"/><path class="y1ejnebhn"/><path class="azg-b8b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:alarmclock" /></template>
