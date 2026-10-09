<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkj4mhl3n.css';
import '../../css/p/p8l4h7b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kkj4mhl3n"/><path class="p8l4h7b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fridge-20-bold" /></template>
