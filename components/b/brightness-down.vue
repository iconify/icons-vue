<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnbgkub4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qnbgkub4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:brightness-down" /></template>
