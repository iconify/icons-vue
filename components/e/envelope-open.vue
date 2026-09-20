<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy_jm2heq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uy_jm2heq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:envelope-open" /></template>
