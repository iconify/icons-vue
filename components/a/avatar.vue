<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1p-jyv8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w1p-jyv8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:avatar" /></template>
