<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzrpw52gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzrpw52gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-dot-solid" /></template>
