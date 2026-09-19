<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrbueyx2o.css';
import '../../css/g/gmoythb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrbueyx2o"/><path class="gmoythb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-volume-full" /></template>
