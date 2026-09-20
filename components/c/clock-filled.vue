<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc5ee2brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc5ee2brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:clock-filled" /></template>
