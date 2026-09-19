<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrrzcn2dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vrrzcn2dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:brazilian-real-sign" /></template>
