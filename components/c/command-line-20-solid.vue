<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avvye0btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="avvye0btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:command-line-20-solid" /></template>
