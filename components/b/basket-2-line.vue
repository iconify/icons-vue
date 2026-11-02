<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2v6t19zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2v6t19zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basket-2-line" /></template>
