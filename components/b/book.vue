<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htudycbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="htudycbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:book" /></template>
