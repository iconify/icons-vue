<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6qlqben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="hd6qlqben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:bell-disabled" /></template>
