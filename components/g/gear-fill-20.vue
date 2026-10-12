<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8swt4bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g8swt4bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-fill-20" /></template>
