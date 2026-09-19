<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8bj94bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h8bj94bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-moon-rain" /></template>
