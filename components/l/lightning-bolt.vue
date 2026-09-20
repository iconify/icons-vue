<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di4r6q8zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="di4r6q8zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:lightning-bolt" /></template>
