<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndycdl2mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndycdl2mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:back-arrow" /></template>
