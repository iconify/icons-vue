<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buok6acvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="buok6acvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angles-right" /></template>
