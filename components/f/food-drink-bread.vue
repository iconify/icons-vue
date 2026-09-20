<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud_o9x3-n.css';
import '../../css/w/wbdo44kuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ud_o9x3-n"/><path class="wbdo44kuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-bread" /></template>
