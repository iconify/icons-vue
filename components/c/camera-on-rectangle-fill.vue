<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q17hu-xfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q17hu-xfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera-on-rectangle-fill" /></template>
