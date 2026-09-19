<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6lprsbiy.css';
import '../../css/s/snqitqbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6lprsbiy"/><path class="snqitqbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:agent-detached" /></template>
