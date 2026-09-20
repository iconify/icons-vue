<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7q-6bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gy7q-6bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:leantime-light" /></template>
