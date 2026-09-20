<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxjlgk8tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxjlgk8tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:combine" /></template>
