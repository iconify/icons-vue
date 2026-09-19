<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsg7zgmqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="tsg7zgmqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:google-drive" /></template>
