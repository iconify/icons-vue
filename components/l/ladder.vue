<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv4u5ht1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dv4u5ht1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ladder" /></template>
