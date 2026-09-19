<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pypo4hbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pypo4hbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blacksmallsquare" /></template>
