<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_zl8bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="zi_zl8bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-knight" /></template>
