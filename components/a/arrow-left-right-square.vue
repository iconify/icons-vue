<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu5-snb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mu5-snb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-right-square" /></template>
