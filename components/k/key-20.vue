<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhrs8tbov.css';
import '../../css/r/rc9exabgm.css';
import '../../css/o/otv_07rxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mhrs8tbov"/><path class="rc9exabgm"/><path class="otv_07rxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-20" /></template>
