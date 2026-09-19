<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsk4eezsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fsk4eezsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:laptop-selected" /></template>
