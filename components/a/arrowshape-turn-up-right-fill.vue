<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_bfxb-og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d_bfxb-og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-right-fill" /></template>
