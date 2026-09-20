<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o03zinb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o03zinb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:code" /></template>
