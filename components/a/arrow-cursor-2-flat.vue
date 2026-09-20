<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkdfvacrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hkdfvacrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-cursor-2-flat" /></template>
