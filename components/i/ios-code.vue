<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt5z90bty.css';
import '../../css/o/op7udfbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt5z90bty"/><path class="op7udfbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-code" /></template>
