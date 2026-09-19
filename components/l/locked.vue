<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvcs4u9hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvcs4u9hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:locked" /></template>
