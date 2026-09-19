<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tera5-bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="tera5-bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:kiwi-bird" /></template>
