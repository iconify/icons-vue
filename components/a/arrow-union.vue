<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qap3ypbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qap3ypbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-union" /></template>
