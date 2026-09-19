<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy6vkbrs.css';
import '../../css/q/qrtxhqwfd.css';
import '../../css/r/r4p2dtbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoy6vkbrs"/><path class="qrtxhqwfd"/><path class="r4p2dtbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-images" /></template>
