<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vgbcb_s.css';
import '../../css/z/zjiwecbao.css';
import '../../css/b/b1mhhebzu.css';
import '../../css/d/d8x7f6q1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="zjiwecbao"/><path class="b1mhhebzu"/><path class="d8x7f6q1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ge-4x3" /></template>
