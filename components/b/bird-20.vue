<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idk0xib5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="idk0xib5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-20" /></template>
