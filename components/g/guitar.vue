<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw56qbcjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iw56qbcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:guitar" /></template>
