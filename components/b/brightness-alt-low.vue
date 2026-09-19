<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeks_sl8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jeks_sl8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-alt-low" /></template>
