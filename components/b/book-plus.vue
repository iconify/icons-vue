<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbw81nbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbw81nbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-plus" /></template>
