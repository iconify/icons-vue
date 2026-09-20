<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pug4ir7hv.css';
import '../../css/c/crznqgb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="pug4ir7hv"/><path class="crznqgb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:enter-down" /></template>
