<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmuq50euc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":640};
const content = `<path class="pmuq50euc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:list" /></template>
