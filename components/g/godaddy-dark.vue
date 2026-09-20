<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr7fluyjp.css';
import '../../css/k/k295tibms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":166,"height":34};
const content = `<path class="dr7fluyjp prefix__path-mobile"/><path class="k295tibms prefix__path-desktop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:godaddy-dark" /></template>
