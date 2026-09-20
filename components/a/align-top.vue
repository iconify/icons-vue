<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8fvoacxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c8fvoacxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:align-top" /></template>
