<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzlj61byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzlj61byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:knip" /></template>
