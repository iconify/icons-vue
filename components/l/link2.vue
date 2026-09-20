<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvzoobc8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvzoobc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link2" /></template>
