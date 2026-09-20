<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkeby_fxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkeby_fxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list3-filled" /></template>
