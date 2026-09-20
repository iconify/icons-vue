<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unt8ljbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unt8ljbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deutsche-bank" /></template>
