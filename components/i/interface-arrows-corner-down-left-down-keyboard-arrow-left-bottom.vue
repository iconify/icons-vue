<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zli93rbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zli93rbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-corner-down-left-down-keyboard-arrow-left-bottom" /></template>
