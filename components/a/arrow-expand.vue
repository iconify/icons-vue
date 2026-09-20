<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-2io57o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wm-2io57o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:arrow-expand" /></template>
