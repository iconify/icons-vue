<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywe4se04n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywe4se04n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hackster" /></template>
