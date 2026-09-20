<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll6i8wx_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ll6i8wx_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:laptop" /></template>
