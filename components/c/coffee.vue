<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jw2n68b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6jw2n68b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:coffee" /></template>
