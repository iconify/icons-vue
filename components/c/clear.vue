<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw4_6ch_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gw4_6ch_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clear" /></template>
