<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu9wddprx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bu9wddprx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-down-circle" /></template>
