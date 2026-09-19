<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lab98_byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lab98_byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hp" /></template>
