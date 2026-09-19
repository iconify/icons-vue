<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1eird_2e.css';
import '../../css/u/uu2dy8rgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1eird_2e"/><path class="uu2dy8rgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-roll" /></template>
