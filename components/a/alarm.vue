<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdk6vth3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rdk6vth3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:alarm" /></template>
