<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd-lhxbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd-lhxbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-speedometer" /></template>
