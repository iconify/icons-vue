<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ippu6y8jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ippu6y8jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daylog-light" /></template>
