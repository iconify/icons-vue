<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4-0ybc2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1280};
const content = `<path class="s4-0ybc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bars" /></template>
