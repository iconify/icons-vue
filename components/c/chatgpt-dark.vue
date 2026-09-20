<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnuiw5usx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnuiw5usx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chatgpt-dark" /></template>
