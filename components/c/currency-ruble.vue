<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr5wehbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr5wehbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-ruble" /></template>
