<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jxmnk027l.css';
import '../../css/g/gjq7b_bis.css';
import '../../css/m/mj-s9sabh.css';
import '../../css/t/tka6adb0f.css';
import '../../css/l/lqrrs8buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jxmnk027l"/><path class="gjq7b_bis"/><path class="mj-s9sabh"/><path class="tka6adb0f"/><path class="lqrrs8buw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incognito-broken" /></template>
