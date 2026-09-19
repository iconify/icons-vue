<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwjpuk8ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwjpuk8ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cube" /></template>
