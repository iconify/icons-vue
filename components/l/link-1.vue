<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4tw58c5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y4tw58c5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:link-1" /></template>
