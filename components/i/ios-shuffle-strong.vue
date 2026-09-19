<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj3y0cblt.css';
import '../../css/v/v2096mbgt.css';
import '../../css/g/gr_mehv_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj3y0cblt"/><path class="v2096mbgt"/><path class="gr_mehv_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-shuffle-strong" /></template>
