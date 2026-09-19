<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0p73jorn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i0p73jorn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-30" /></template>
