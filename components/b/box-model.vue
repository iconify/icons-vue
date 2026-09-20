<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrrfv2bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zrrfv2bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:box-model" /></template>
