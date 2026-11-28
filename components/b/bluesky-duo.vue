<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkz86tbnb.css';
import '../../css/t/tlq2l5bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkz86tbnb secondary"/><path class="primary tlq2l5bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluesky-duo" /></template>
