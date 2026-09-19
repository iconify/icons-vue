<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn93d6aes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xn93d6aes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:indent-left" /></template>
