<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv17atbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv17atbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:kettle" /></template>
