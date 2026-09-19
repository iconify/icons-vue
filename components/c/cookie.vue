<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6g_mujle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6g_mujle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cookie" /></template>
