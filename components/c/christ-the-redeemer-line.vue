<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq6gbbbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq6gbbbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christ-the-redeemer-line" /></template>
