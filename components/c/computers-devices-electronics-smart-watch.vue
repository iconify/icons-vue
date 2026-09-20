<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhjs9ibxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zhjs9ibxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-smart-watch" /></template>
