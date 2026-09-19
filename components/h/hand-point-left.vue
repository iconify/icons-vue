<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/val3symhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="val3symhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-point-left" /></template>
