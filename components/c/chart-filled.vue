<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whqrdobun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whqrdobun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-filled" /></template>
