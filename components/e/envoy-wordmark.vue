<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbr1fpbxs.css';
import '../../css/u/u5wuxiadc.css';
import '../../css/t/t_4e8hb_x.css';
import '../../css/j/jdpmspbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xbr1fpbxs"/><path class="u5wuxiadc"/><path class="t_4e8hb_x"/><path class="jdpmspbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:envoy-wordmark" /></template>
