<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yycsh22_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yycsh22_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:jumpto-expressive" /></template>
