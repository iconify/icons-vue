<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h52hq6b9u.css';
import '../../css/z/z9kgvgb1l.css';
import '../../css/w/wfiv04kcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h52hq6b9u"/><path class="z9kgvgb1l"/><path class="wfiv04kcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-off-outline" /></template>
