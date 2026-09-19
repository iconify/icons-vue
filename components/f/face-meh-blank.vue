<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkq1b1b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xkq1b1b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-meh-blank" /></template>
