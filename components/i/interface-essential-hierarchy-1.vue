<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1verwbwl.css';
import '../../css/g/g2r24b_3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1verwbwl"/><path class="g2r24b_3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-hierarchy-1" /></template>
