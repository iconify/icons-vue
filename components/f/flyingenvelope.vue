<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucg8xbjld.css';
import '../../css/y/yqufnccgb.css';
import '../../css/d/dnu_c0bhd.css';
import '../../css/i/icqaqiboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucg8xbjld"/><path class="yqufnccgb"/><path class="dnu_c0bhd"/><path class="icqaqiboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:flyingenvelope" /></template>
