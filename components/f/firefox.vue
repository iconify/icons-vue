<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiz3a5bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fiz3a5bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:firefox" /></template>
