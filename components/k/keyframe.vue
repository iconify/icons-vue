<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbt_o16fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbt_o16fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe" /></template>
