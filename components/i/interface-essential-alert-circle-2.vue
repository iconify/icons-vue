<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfnphxbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfnphxbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-alert-circle-2" /></template>
