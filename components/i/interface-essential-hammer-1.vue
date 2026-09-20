<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g154nh6_x.css';
import '../../css/b/b_5co9z5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g154nh6_x"/><path class="b_5co9z5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-hammer-1" /></template>
