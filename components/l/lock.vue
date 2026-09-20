<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6vai-59c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c6vai-59c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:lock" /></template>
