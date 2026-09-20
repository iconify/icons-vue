<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fge55pbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fge55pbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:desktop" /></template>
