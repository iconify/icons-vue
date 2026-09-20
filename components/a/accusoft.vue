<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv2g0pfea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv2g0pfea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:accusoft" /></template>
