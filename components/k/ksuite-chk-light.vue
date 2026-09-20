<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfusopbkd.css';
import '../../css/j/jx1d2towh.css';
import '../../css/x/xj6r9dbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfusopbkd"/><path class="jx1d2towh"/><path class="xj6r9dbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-chk-light" /></template>
