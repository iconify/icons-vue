<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj_7ijbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj_7ijbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-fastforward" /></template>
