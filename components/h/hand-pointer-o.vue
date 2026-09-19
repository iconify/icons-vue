<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgo980z3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="sgo980z3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-pointer-o" /></template>
