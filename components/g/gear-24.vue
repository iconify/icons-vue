<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6wgzy02y.css';
import '../../css/r/rhjnb0hvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6wgzy02y"/><path class="rhjnb0hvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gear-24" /></template>
