<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/focov3bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2368,"height":1664};
const content = `<path class="focov3bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:id-card-alt" /></template>
