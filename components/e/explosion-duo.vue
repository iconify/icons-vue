<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w44k3_byo.css';
import '../../css/d/di2c6dxli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w44k3_byo"/><path class="di2c6dxli primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:explosion-duo" /></template>
