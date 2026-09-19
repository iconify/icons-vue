<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la9q-q5df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="la9q-q5df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:buffer-time-after" /></template>
