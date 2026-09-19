<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw1p922ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw1p922ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:airplane" /></template>
