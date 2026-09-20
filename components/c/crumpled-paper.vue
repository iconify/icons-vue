<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s43rqw6eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s43rqw6eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:crumpled-paper" /></template>
