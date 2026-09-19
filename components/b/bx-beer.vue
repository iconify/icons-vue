<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm4e34bbn.css';
import '../../css/j/jab1lr5xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm4e34bbn"/><path class="jab1lr5xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-beer" /></template>
