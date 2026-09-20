<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkkm2snmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="xkkm2snmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:forward-circle" /></template>
