<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxwy_hw-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxwy_hw-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-cross-finger-heart" /></template>
