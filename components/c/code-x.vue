<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex4rp8bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex4rp8bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:code-x" /></template>
