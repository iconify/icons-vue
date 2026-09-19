<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzzz3ybdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qzzz3ybdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gobackward" /></template>
