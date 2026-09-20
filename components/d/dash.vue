<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqfvs8b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kqfvs8b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dash" /></template>
