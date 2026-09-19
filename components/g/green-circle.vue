<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idh4sbcyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="idh4sbcyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:green-circle" /></template>
