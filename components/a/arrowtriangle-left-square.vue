<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6h2mp5hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t6h2mp5hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-left-square" /></template>
