<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wra2vxbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wra2vxbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-left" /></template>
