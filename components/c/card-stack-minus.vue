<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-2stacov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n-2stacov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:card-stack-minus" /></template>
