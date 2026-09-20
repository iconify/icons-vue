<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-wis1b_l.css';
import '../../css/j/jfggo2b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j-wis1b_l"/><path class="jfggo2b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-alert-triangle-2" /></template>
