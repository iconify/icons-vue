<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg7n7en_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xg7n7en_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:card-stack-plus" /></template>
