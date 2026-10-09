<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjr53p4wm.css';
import '../../css/j/jx_02mklt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjr53p4wm"/><path class="jx_02mklt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-20-bold" /></template>
