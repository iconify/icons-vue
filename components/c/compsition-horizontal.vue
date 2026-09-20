<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8i-aqr8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l8i-aqr8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:compsition-horizontal" /></template>
