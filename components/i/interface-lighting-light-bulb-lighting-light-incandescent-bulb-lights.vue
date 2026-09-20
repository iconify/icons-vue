<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9anvvtig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r9anvvtig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-lighting-light-bulb-lighting-light-incandescent-bulb-lights" /></template>
