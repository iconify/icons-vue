<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hava717ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hava717ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fulcrum" /></template>
