<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrrye30mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrrye30mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-color-palette" /></template>
