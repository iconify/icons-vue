<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_pzyr42v.css';
import '../../css/f/f5mkxw1-g.css';
import '../../css/q/qqj91ccql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_pzyr42v"/><path class="f5mkxw1-g"/><path class="qqj91ccql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:documents" /></template>
