<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iplssnb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iplssnb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hockey-puck" /></template>
