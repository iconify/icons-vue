<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7y6rbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lk7y6rbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-20-bold" /></template>
