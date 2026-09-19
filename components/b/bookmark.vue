<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo--jxzmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jo--jxzmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bookmark" /></template>
