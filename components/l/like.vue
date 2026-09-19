<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji5yl_z2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="ji5yl_z2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:like" /></template>
