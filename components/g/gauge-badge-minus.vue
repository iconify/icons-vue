<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzfjlrq1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fzfjlrq1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gauge-badge-minus" /></template>
