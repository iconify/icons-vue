<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz06rjcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jz06rjcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:booty" /></template>
