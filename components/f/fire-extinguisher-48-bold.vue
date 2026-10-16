<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r42xl0rkz.css';
import '../../css/w/wwqvuwc3u.css';
import '../../css/a/ae677qkzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r42xl0rkz"/><path class="wwqvuwc3u"/><path class="ae677qkzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-extinguisher-48-bold" /></template>
