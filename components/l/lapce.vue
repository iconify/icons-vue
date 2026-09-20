<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlilyp2hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlilyp2hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lapce" /></template>
