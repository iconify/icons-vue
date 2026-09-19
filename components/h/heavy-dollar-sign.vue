<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du7ckob0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="du7ckob0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heavy-dollar-sign" /></template>
