<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fro1igbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fro1igbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-left-down" /></template>
