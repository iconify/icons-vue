<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1klr8o9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u1klr8o9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bitcoin" /></template>
