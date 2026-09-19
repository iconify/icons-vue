<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnh568b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hnh568b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-swap" /></template>
