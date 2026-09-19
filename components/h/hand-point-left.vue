<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keh4ghbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="keh4ghbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-point-left" /></template>
