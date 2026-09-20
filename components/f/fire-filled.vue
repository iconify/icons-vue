<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv1__2_yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1__2_yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fire-filled" /></template>
