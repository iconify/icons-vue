<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sftdpohbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sftdpohbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:expand-down" /></template>
