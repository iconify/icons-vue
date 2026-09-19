<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj184cc4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="vj184cc4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:chess-bishop" /></template>
