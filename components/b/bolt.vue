<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvb524s4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dvb524s4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bolt" /></template>
