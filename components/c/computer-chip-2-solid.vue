<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn7h7bcbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hn7h7bcbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-chip-2-solid" /></template>
