<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k15v96bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k15v96bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:chevron-right" /></template>
