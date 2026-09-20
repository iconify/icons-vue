<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fklcugbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fklcugbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:block-2-remix" /></template>
