<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7txlobxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7txlobxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gl-inet" /></template>
