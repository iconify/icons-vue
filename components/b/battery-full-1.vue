<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luhxm1b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="luhxm1b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-full-1" /></template>
