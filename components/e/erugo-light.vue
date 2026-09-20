<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhbyxpbbq.css';
import '../../css/p/pk02s0tyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhbyxpbbq"/><path class="pk02s0tyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:erugo-light" /></template>
