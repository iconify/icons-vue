<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm_c2mbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wm_c2mbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-diagonal-top-left" /></template>
