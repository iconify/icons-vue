<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n__gb0bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n__gb0bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-indent-increase" /></template>
