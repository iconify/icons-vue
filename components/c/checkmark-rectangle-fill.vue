<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iix0k_bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iix0k_bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-rectangle-fill" /></template>
