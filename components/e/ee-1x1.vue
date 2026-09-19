<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdia6fa5z.css';
import '../../css/q/q2l4humxv.css';
import '../../css/m/me0wbo9yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdia6fa5z"/><path class="q2l4humxv"/><path class="me0wbo9yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ee-1x1" /></template>
