<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs2m-5bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2m-5bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:happycow" /></template>
