<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afqa3ibvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afqa3ibvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:chess-queen" /></template>
