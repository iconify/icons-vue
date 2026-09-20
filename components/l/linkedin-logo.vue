<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgblf3b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tgblf3b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:linkedin-logo" /></template>
