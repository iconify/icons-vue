<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vop2ck--i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vop2ck--i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:github" /></template>
