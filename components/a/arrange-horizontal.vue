<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf19blzpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pf19blzpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrange-horizontal" /></template>
