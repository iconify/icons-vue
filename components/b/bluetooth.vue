<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpkbf0bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpkbf0bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bluetooth" /></template>
