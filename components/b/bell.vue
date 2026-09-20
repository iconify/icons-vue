<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4zwn-thk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w4zwn-thk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bell" /></template>
