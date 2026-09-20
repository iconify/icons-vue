<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c93l_8bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c93l_8bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:camera" /></template>
