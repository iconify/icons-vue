<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2z_a4ykj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2z_a4ykj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hackerearth" /></template>
