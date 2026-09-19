<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu44icb9g.css';
import '../../css/l/l3a29xfgf.css';
import '../../css/v/vuq4s9bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="vu44icb9g"/><path class="l3a29xfgf"/><path class="vuq4s9bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:am-4x3" /></template>
