<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc_wy4d_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vc_wy4d_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:loop-outline" /></template>
