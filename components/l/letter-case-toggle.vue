<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3b927b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k3b927b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:letter-case-toggle" /></template>
