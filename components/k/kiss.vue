<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2cxap5ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="w2cxap5ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:kiss" /></template>
