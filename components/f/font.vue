<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oha6hnoud.css';
import '../../css/c/c8_pid-oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oha6hnoud"/><path class="c8_pid-oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:font" /></template>
