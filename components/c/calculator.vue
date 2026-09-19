<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubuoos49l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubuoos49l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:calculator" /></template>
