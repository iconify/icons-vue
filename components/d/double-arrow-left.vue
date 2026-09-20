<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsuyl5yrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wsuyl5yrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:double-arrow-left" /></template>
