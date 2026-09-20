<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp2y9kbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cp2y9kbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:disc" /></template>
