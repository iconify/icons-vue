<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao-mrdbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ao-mrdbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-right-20" /></template>
