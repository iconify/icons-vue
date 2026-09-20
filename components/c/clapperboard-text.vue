<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wanp_dc4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wanp_dc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-text" /></template>
