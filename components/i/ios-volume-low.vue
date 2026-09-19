<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlwegtczi.css';
import '../../css/t/t4u_3fbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlwegtczi"/><path class="t4u_3fbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-volume-low" /></template>
