<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo-rlxbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uo-rlxbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:chevron-left" /></template>
