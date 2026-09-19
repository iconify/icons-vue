<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4-2d34yr.css';
import '../../css/h/hqoymybvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c4-2d34yr"/><path class="hqoymybvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-box-outline" /></template>
