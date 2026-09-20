<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmz2_w97h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmz2_w97h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:label-filled" /></template>
