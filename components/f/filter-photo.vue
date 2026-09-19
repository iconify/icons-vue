<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4sk93ouz.css';
import '../../css/z/zqq79db7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4sk93ouz"/><path class="zqq79db7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:filter-photo" /></template>
