<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvqs58b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uvqs58b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:info-circled" /></template>
