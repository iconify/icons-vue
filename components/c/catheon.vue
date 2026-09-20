<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8qw16bmp.css';
import '../../css/r/rqcx1bj2b.css';
import '../../css/u/udfii55xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8qw16bmp"/><path class="rqcx1bj2b"/><path class="udfii55xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:catheon" /></template>
