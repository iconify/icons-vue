<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zytnknbqy.css';
import '../../css/h/hxrdmob8v.css';
import '../../css/j/j1_yf7_6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zytnknbqy"/><path class="hxrdmob8v"/><path class="j1_yf7_6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:factory-breakdown" /></template>
