<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krk_5tb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krk_5tb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-messenger" /></template>
