<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-98_hbbz.css';
import '../../css/z/zl44w455k.css';
import '../../css/i/ihr8kgbqh.css';
import '../../css/h/hm7iy3b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-98_hbbz"/><path class="zl44w455k"/><path class="ihr8kgbqh"/><path class="hm7iy3b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-image" /></template>
