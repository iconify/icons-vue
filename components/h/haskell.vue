<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijq4zybyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ijq4zybyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:haskell" /></template>
