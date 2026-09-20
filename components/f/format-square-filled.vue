<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8khc1bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8khc1bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:format-square-filled" /></template>
