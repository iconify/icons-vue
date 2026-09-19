<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-im0-bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i-im0-bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:backward-end-alt" /></template>
