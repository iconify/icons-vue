<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy7xqk_um.css';
import '../../css/y/yyty6bb4a.css';
import '../../css/w/w5dpz7-za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="yyty6bb4a"/><path class="w5dpz7-za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-3x3-48-bold" /></template>
