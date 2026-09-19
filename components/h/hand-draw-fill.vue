<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di-eyczor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="di-eyczor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-draw-fill" /></template>
