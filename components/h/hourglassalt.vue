<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr3zg3byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zr3zg3byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hourglassalt" /></template>
