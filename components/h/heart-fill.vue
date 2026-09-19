<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjoaa4bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hjoaa4bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:heart-fill" /></template>
