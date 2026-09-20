<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo9crpaok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo9crpaok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-size-line" /></template>
